<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo0xiccmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo0xiccmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:pin" {...props}></Icon>
