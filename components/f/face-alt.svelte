<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qilianfni.css';
import '../../css/b/bv-ewi9vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qilianfni"/><path class="bv-ewi9vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:face-alt" {...props}></Icon>
