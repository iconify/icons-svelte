<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx5yyubuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx5yyubuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:duplicate" {...props}></Icon>
