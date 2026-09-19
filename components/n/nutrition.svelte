<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/dkwmvxcqz.css';
import '../../css/q/q7kngdcwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="dkwmvxcqz"/><path class="q7kngdcwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:nutrition" {...props}></Icon>
