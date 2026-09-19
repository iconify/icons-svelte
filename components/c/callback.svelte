<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbai33bej.css';
import '../../css/w/wtfmx7b3v.css';
import '../../css/z/z6ykmyhyu.css';
import '../../css/q/qtw6_-box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xbai33bej"/><g class="wtfmx7b3v"><path class="z6ykmyhyu"/><path class="qtw6_-box"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:callback" {...props}></Icon>
