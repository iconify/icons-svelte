<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f40vwcb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f40vwcb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:border-bottom" {...props}></Icon>
