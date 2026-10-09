<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p93n1m73s.css';
import '../../css/t/tgao99i9c.css';
import '../../css/q/qg0hzccxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p93n1m73s"/><path class="tgao99i9c"/><path class="qg0hzccxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:archive-20" {...props}></Icon>
