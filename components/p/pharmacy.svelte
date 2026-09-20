<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/h/h56qdhbsd.css';
import '../../css/l/lfpfzkb3s.css';
import '../../css/x/xg5z2wbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="h56qdhbsd"/><path class="lfpfzkb3s"/><path class="xg5z2wbhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pharmacy" {...props}></Icon>
