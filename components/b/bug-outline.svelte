<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1jnopb3d.css';
import '../../css/l/l3z28ebpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w1jnopb3d"/><path class="l3z28ebpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bug-outline" {...props}></Icon>
