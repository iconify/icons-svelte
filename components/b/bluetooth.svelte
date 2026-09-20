<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5yqsl18x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5yqsl18x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:bluetooth" {...props}></Icon>
