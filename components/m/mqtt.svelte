<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jexh1wtrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jexh1wtrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mqtt" {...props}></Icon>
