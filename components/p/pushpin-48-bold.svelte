<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7aw6lb_z.css';
import '../../css/b/b9njywbbk.css';
import '../../css/u/uyyqc0_4u.css';
import '../../css/t/tyapp0bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c7aw6lb_z"/><path class="b9njywbbk"/><path class="uyyqc0_4u"/><path class="tyapp0bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pushpin-48-bold" {...props}></Icon>
