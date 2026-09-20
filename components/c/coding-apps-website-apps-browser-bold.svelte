<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6xfrmbct.css';
import '../../css/u/u4aylz3fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6xfrmbct"/><path class="u4aylz3fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-apps-browser-bold" {...props}></Icon>
