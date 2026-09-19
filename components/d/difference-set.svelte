<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhs0kabae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qhs0kabae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:difference-set" {...props}></Icon>
