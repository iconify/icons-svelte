<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urvd_efow.css';
import '../../css/i/iqsbobj2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="urvd_efow"/><path class="iqsbobj2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-attachment-open" {...props}></Icon>
