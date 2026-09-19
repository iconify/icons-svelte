<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaxi7qn1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vaxi7qn1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:adversal" {...props}></Icon>
