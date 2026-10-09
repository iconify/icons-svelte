<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-g74icta.css';
import '../../css/z/ze1r_ccem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="ze1r_ccem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-check-20" {...props}></Icon>
