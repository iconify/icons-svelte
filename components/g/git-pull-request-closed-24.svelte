<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u89qm5-sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u89qm5-sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-pull-request-closed-24" {...props}></Icon>
