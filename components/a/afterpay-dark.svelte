<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy37wkf-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":23};
const content = `<path class="wy37wkf-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:afterpay-dark" {...props}></Icon>
