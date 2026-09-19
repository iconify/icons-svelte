<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw7-gdcrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw7-gdcrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:facebook-filled" {...props}></Icon>
