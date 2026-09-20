<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9_amsz7a.css';
import '../../css/t/t7parlbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h9_amsz7a"/><path class="t7parlbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-log-open" {...props}></Icon>
