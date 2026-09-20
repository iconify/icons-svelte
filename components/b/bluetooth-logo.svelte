<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfm6axtfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfm6axtfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bluetooth-logo" {...props}></Icon>
