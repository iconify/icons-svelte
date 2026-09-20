<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3ppyw0-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3ppyw0-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-align-justify" {...props}></Icon>
