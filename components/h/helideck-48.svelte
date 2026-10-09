<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-j1i2muo.css';
import '../../css/q/qxu7-jb9g.css';
import '../../css/e/e647zfbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c-j1i2muo"/><path class="qxu7-jb9g"/><path class="e647zfbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:helideck-48" {...props}></Icon>
