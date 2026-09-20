<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k62k3eb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k62k3eb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left4" {...props}></Icon>
