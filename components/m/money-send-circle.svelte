<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wkm6c6j9i.css';
import '../../css/d/dkfqmgbcg.css';
import '../../css/z/zlkcfkcwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wkm6c6j9i"/><path class="dkfqmgbcg"/><path class="zlkcfkcwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-send-circle" {...props}></Icon>
