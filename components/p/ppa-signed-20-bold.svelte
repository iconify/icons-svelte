<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1t7v_btd.css';
import '../../css/p/pufx9lxgz.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x1t7v_btd"/><path class="pufx9lxgz"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ppa-signed-20-bold" {...props}></Icon>
