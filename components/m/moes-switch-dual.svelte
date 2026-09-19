<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k49k42c2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k49k42c2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:moes-switch-dual" {...props}></Icon>
