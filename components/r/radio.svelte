<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj-1rxbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj-1rxbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:radio" {...props}></Icon>
