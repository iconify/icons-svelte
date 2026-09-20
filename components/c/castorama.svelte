<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idf37dbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idf37dbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:castorama" {...props}></Icon>
