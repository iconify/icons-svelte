<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2dtslp_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2dtslp_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-bottom3" {...props}></Icon>
