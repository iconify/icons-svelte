<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe8xottkx.css';
import '../../css/w/wh1r03b-i.css';
import '../../css/k/k3lgfsb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qe8xottkx"/><path class="wh1r03b-i"/><path class="k3lgfsb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-cable-48-bold" {...props}></Icon>
