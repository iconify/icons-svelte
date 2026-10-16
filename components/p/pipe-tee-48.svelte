<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3hnj1bgs.css';
import '../../css/n/ng_3h1b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g3hnj1bgs"/><path class="ng_3h1b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-tee-48" {...props}></Icon>
