<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bct-im56e.css';
import '../../css/t/tqb_6nb6c.css';
import '../../css/m/mykin67du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="bct-im56e"/><circle class="tqb_6nb6c"/><circle class="mykin67du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:more" {...props}></Icon>
