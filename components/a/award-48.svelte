<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7kugr3av.css';
import '../../css/b/bqdx-xuwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b7kugr3av"/><path class="bqdx-xuwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:award-48" {...props}></Icon>
