<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg6zdebrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg6zdebrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openssl" {...props}></Icon>
