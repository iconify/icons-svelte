<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifivasbnp.css';
import '../../css/p/ptb97odfw.css';
import '../../css/d/dmmpmib0w.css';
import '../../css/y/yr6a_mbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ifivasbnp"/><path class="ptb97odfw"/><path class="dmmpmib0w"/><path class="yr6a_mbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackpennant" {...props}></Icon>
