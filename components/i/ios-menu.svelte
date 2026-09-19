<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2pty-1kt.css';
import '../../css/c/cad1wdxuy.css';
import '../../css/n/n1y99614y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q2pty-1kt"/><path class="cad1wdxuy"/><path class="n1y99614y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-menu" {...props}></Icon>
