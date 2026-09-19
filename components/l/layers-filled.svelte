<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-bbnvbzg.css';
import '../../css/m/mvcw08bgw.css';
import '../../css/a/akdbaebrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-bbnvbzg"/><path class="mvcw08bgw"/><path class="akdbaebrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-filled" {...props}></Icon>
