<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdo397bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdo397bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apple-keyboard-option" {...props}></Icon>
