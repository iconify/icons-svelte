<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcvd2fbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mcvd2fbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-git-branch" {...props}></Icon>
