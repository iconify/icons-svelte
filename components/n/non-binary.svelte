<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhlftk48t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhlftk48t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:non-binary" {...props}></Icon>
