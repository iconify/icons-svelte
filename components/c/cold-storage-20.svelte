<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyvjvhb1l.css';
import '../../css/z/zrqlkvb4c.css';
import '../../css/o/oov7epbkt.css';
import '../../css/h/hh-vtxt5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zyvjvhb1l"/><path class="zrqlkvb4c"/><path class="oov7epbkt"/><path class="hh-vtxt5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cold-storage-20" {...props}></Icon>
