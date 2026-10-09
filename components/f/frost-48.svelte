<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhtqqrbcl.css';
import '../../css/g/gdgkf1jwj.css';
import '../../css/w/wu47-njnc.css';
import '../../css/w/w025bmewr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zhtqqrbcl"/><path class="gdgkf1jwj"/><path class="wu47-njnc"/><path class="w025bmewr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frost-48" {...props}></Icon>
