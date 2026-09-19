<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df254mb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="df254mb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:play-one" {...props}></Icon>
