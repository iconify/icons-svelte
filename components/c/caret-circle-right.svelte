<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjy_-lbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjy_-lbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:caret-circle-right" {...props}></Icon>
