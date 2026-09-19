<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyf3ue2rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yyf3ue2rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:brush" {...props}></Icon>
