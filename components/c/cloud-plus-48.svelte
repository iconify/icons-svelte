<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m77m-bb1r.css';
import '../../css/f/f5bqv3-2b.css';
import '../../css/d/dq0waab5c.css';
import '../../css/y/yoxyoac9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m77m-bb1r"/><path class="f5bqv3-2b"/><path class="dq0waab5c"/><path class="yoxyoac9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-plus-48" {...props}></Icon>
