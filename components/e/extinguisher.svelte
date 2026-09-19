<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwp_pubaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":832,"height":1024};
const content = `<path class="xwp_pubaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:extinguisher" {...props}></Icon>
