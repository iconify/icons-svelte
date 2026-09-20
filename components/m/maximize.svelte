<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn1n6ybcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn1n6ybcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:maximize" {...props}></Icon>
