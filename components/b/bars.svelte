<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmk7s0b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmk7s0b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:bars" {...props}></Icon>
