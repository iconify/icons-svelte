<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krg4aibpx.css';
import '../../css/z/z68qmysoe.css';
import '../../css/s/s3_8gac3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="krg4aibpx"/><path class="z68qmysoe"/><path class="s3_8gac3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-pentagon" {...props}></Icon>
