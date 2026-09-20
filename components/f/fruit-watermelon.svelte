<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok0humyuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok0humyuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fruit-watermelon" {...props}></Icon>
