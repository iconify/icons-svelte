<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5eyd222o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5eyd222o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pulse" {...props}></Icon>
