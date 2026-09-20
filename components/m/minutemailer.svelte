<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi81_1wwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi81_1wwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:minutemailer" {...props}></Icon>
