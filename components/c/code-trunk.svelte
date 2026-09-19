<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh_nvlg2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xh_nvlg2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:code-trunk" {...props}></Icon>
