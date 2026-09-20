<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en1kotbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en1kotbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-bottom-simple-line" {...props}></Icon>
