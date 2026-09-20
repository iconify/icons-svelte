<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kov7snrof.css';
import '../../css/a/a076kccfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kov7snrof"/><path class="a076kccfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-review-open" {...props}></Icon>
