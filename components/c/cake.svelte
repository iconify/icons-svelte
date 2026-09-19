<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whj_4pbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whj_4pbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cake" {...props}></Icon>
