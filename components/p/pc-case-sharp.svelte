<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qit8fdbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qit8fdbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:pc-case-sharp" {...props}></Icon>
