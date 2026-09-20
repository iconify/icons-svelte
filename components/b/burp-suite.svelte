<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc1z1abbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc1z1abbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:burp-suite" {...props}></Icon>
