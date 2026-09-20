<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwp21cyvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwp21cyvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-colour-highlight" {...props}></Icon>
