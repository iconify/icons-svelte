<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu4v_kdxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tu4v_kdxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calculator-fill" {...props}></Icon>
