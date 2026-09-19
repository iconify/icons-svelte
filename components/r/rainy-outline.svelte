<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppih4zbbb.css';
import '../../css/o/o92kdvbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ppih4zbbb"/><path class="o92kdvbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:rainy-outline" {...props}></Icon>
