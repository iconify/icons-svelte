<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyg0w2hhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyg0w2hhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dlthub" {...props}></Icon>
