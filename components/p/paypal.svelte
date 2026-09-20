<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq0ehjb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq0ehjb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:paypal" {...props}></Icon>
