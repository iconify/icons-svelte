<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n__6aluxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b n__6aluxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:dot-env" {...props}></Icon>
