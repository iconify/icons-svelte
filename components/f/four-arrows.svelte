<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd-6131oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qd-6131oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:four-arrows" {...props}></Icon>
