<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-tp38bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-tp38bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:elipse-frame-solid" {...props}></Icon>
