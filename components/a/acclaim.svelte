<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdlufvbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="rdlufvbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:acclaim" {...props}></Icon>
