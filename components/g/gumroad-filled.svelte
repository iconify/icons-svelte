<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm5ydabof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm5ydabof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:gumroad-filled" {...props}></Icon>
