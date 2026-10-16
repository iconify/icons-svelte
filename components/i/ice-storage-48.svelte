<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-wxdblp.css';
import '../../css/e/ewoso7beo.css';
import '../../css/w/wabkd6bsw.css';
import '../../css/j/jwu10ccso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ie-wxdblp"/><path class="ewoso7beo"/><path class="wabkd6bsw"/><path class="jwu10ccso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ice-storage-48" {...props}></Icon>
