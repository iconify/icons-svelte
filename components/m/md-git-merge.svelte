<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzf2spbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bzf2spbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-git-merge" {...props}></Icon>
