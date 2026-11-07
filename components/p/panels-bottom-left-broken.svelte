<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tcg0b8fzd.css';
import '../../css/y/yzl97151b.css';
import '../../css/a/a20bergfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tcg0b8fzd"/><path class="yzl97151b"/><path class="a20bergfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-bottom-left-broken" {...props}></Icon>
