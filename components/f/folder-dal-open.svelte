<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpub25bol.css';
import '../../css/b/bngdwyyjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpub25bol"/><path class="bngdwyyjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-dal-open" {...props}></Icon>
