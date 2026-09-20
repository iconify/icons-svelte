<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw6bhtqns.css';
import '../../css/s/sfw4e80bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw6bhtqns"/><path class="sfw4e80bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-clone-24" {...props}></Icon>
