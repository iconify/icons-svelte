<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/o/olsnk6fpy.css';
import '../../css/z/z9wgtxbsj.css';
import '../../css/f/fpixpmx3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="olsnk6fpy"/><path class="z9wgtxbsj"/><path class="fpixpmx3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:reload" {...props}></Icon>
