<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqnz_wbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqnz_wbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-yandex" {...props}></Icon>
