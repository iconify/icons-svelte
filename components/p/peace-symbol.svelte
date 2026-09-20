<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpjt_glcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mpjt_glcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:peace-symbol" {...props}></Icon>
