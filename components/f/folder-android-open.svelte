<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8rt5bbrs.css';
import '../../css/k/kilgsnbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y8rt5bbrs"/><path class="kilgsnbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-android-open" {...props}></Icon>
