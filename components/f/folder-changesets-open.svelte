<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kov7snrof.css';
import '../../css/l/l5zpj0bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kov7snrof"/><path class="l5zpj0bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-changesets-open" {...props}></Icon>
