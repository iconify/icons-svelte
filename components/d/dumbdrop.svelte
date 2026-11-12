<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbuj3kxuy.css';
import '../../css/x/xl9oz1zix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="mbuj3kxuy"/><path class="xl9oz1zix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbdrop" {...props}></Icon>
