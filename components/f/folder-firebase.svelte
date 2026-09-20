<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsuo4vbmg.css';
import '../../css/l/lhog0tb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nsuo4vbmg"/><path class="lhog0tb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-firebase" {...props}></Icon>
