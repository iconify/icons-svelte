<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnq8786rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnq8786rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:contact-minus" {...props}></Icon>
