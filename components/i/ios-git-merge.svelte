<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbfz-wywq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qbfz-wywq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-git-merge" {...props}></Icon>
