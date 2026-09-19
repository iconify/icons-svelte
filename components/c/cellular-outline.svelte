<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzkebvbwp.css';
import '../../css/h/h3qchvbhn.css';
import '../../css/u/uw1uypbnt.css';
import '../../css/o/o9dpakbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="uzkebvbwp"/><rect class="h3qchvbhn"/><rect class="uw1uypbnt"/><rect class="o9dpakbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cellular-outline" {...props}></Icon>
