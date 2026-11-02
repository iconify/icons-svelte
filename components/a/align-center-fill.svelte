<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfl3-yyya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfl3-yyya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-center-fill" {...props}></Icon>
