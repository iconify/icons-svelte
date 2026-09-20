<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvmdom3gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvmdom3gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:braintree" {...props}></Icon>
