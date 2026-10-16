<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r06i5gaqp.css';
import '../../css/z/zk-ob16tw.css';
import '../../css/l/lhz7cds8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r06i5gaqp"/><path class="zk-ob16tw"/><path class="lhz7cds8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hinge-20" {...props}></Icon>
