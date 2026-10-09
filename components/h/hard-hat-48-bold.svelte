<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w010_tghd.css';
import '../../css/j/jjy_43hmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w010_tghd"/><path class="jjy_43hmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hard-hat-48-bold" {...props}></Icon>
