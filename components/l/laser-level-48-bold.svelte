<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh5lwhb7v.css';
import '../../css/g/gyt736dji.css';
import '../../css/h/hua3e5bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bh5lwhb7v"/><path class="gyt736dji"/><path class="hua3e5bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laser-level-48-bold" {...props}></Icon>
