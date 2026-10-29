<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx94fvtdi.css';
import '../../css/j/j-rz0kfnd.css';
import '../../css/b/bq07eo2pj.css';
import '../../css/b/bjpkh6bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx94fvtdi wm-k"/><path class="j-rz0kfnd wm-a"/><path class="bq07eo2pj wm-a"/><path class="bjpkh6bgj wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:file-spreadsheet" {...props}></Icon>
