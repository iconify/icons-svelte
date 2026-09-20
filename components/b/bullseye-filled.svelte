<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iyx8dpb5p.css';
import '../../css/o/o49gaohmw.css';
import '../../css/q/qrxx6excg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iyx8dpb5p"/><path class="o49gaohmw"/><path class="qrxx6excg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bullseye-filled" {...props}></Icon>
