<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qab7zp_yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qab7zp_yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pet-paw-solid" {...props}></Icon>
