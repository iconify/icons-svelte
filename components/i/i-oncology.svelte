<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6--_rptg.css';
import '../../css/a/a9ty3crzj.css';
import '../../css/w/w8gx8xbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g6--_rptg"/><path class="a9ty3crzj"/><path class="w8gx8xbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-oncology" {...props}></Icon>
