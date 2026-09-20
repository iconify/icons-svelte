<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tta3otbad.css';
import '../../css/z/zza0bbbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tta3otbad"/><path class="zza0bbbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-skills-open" {...props}></Icon>
