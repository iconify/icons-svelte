<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgrtxyi6j.css';
import '../../css/d/dn6i_ub7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cgrtxyi6j"/><path class="dn6i_ub7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:cloud-twotone" {...props}></Icon>
