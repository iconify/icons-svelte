<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsgp-8odn.css';
import '../../css/z/zs1_24dzp.css';
import '../../css/x/xnni9p8to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xsgp-8odn"/><path class="zs1_24dzp"/><path class="xnni9p8to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:recloser-48" {...props}></Icon>
