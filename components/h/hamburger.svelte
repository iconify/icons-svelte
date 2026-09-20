<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/rzc42il7p.css';
import '../../css/x/xeuwd5bbt.css';
import '../../css/h/huilrub5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzc42il7p"/><rect class="xeuwd5bbt"/><path class="huilrub5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:hamburger" {...props}></Icon>
