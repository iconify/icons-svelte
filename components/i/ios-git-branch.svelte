<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnz27eb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hnz27eb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-git-branch" {...props}></Icon>
