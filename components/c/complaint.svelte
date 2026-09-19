<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/oagawgbbv.css';
import '../../css/o/olpgfdb0y.css';
import '../../css/o/olyxe4bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oagawgbbv"/><path class="olpgfdb0y"/><path class="olyxe4bhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:complaint" {...props}></Icon>
