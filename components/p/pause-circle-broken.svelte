<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zxg6-1byk.css';
import '../../css/u/uaiwr_zjy.css';
import '../../css/k/ko6o-6b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zxg6-1byk"/><path class="uaiwr_zjy"/><path class="ko6o-6b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pause-circle-broken" {...props}></Icon>
