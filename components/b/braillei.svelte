<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcdkupb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="pcdkupb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillei" {...props}></Icon>
