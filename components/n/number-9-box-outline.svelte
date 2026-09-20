<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqr4w3gel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqr4w3gel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-9-box-outline" {...props}></Icon>
