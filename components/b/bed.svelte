<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymit52bkh.css';
import '../../css/s/sil2n14km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ymit52bkh"/><path class="sil2n14km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:bed" {...props}></Icon>
