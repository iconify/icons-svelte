<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/b/beip37bcn.css';
import '../../css/w/w4fezhbzj.css';
import '../../css/q/qyky4f0vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="beip37bcn"/><path class="w4fezhbzj"/><path class="qyky4f0vl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:dashboard" {...props}></Icon>
