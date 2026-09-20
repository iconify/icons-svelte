<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_fy9wzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_fy9wzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:elixir" {...props}></Icon>
