<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qugl5fp2v.css';
import '../../css/j/jln5mowjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qugl5fp2v"/><path class="jln5mowjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:delete-twotone" {...props}></Icon>
