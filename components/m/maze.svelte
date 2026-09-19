<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sba_tzbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sba_tzbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:maze" {...props}></Icon>
