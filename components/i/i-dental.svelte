<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed2rjpbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ed2rjpbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-dental" {...props}></Icon>
