<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw23apjax.css';
import '../../css/f/ftl0q4tvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw23apjax"/><path class="ftl0q4tvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-money" {...props}></Icon>
