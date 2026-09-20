<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb5pahitw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb5pahitw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:parity-substrate" {...props}></Icon>
