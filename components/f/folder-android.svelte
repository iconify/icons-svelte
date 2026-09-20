<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n36vjab5v.css';
import '../../css/k/kilgsnbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n36vjab5v"/><path class="kilgsnbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-android" {...props}></Icon>
