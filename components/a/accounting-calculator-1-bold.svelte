<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft06mxbzl.css';
import '../../css/d/dlzqyubkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft06mxbzl"/><path class="dlzqyubkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:accounting-calculator-1-bold" {...props}></Icon>
