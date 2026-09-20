<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlzy7bc8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlzy7bc8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-keep" {...props}></Icon>
