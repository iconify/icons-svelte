<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq3gyotos.css';
import '../../css/v/vhfnlbb4f.css';
import '../../css/x/x87u6nj0f.css';
import '../../css/b/b_mdlt70l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lq3gyotos"/><path class="vhfnlbb4f"/><path class="x87u6nj0f"/><path class="b_mdlt70l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:lamb" {...props}></Icon>
