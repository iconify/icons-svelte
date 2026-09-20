<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk3xrrbnq.css';
import '../../css/c/cjo_bouin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":252};
const content = `<path class="hk3xrrbnq"/><path class="cjo_bouin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mysql-dark" {...props}></Icon>
