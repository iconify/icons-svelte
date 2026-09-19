<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/i/iv6gf1g5l.css';
import '../../css/t/tcrnivb-g.css';
import '../../css/v/vc8ie36qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="iv6gf1g5l"/><path class="tcrnivb-g"/><path class="vc8ie36qx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-download-01" {...props}></Icon>
