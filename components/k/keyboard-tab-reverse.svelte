<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tumxz3yoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tumxz3yoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-tab-reverse" {...props}></Icon>
