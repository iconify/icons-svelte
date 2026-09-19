<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz93zk_kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="zz93zk_kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:largebluecircle" {...props}></Icon>
