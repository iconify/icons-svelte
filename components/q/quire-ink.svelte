<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkufbknyv.css';
import '../../css/m/mb2o3qbdg.css';
import '../../css/g/g1jdu73ab.css';
import '../../css/e/eentqmb8a.css';
import '../../css/p/pq5g1621a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jkufbknyv"/><path class="mb2o3qbdg"/><path class="g1jdu73ab"/><path class="eentqmb8a"/><path class="pq5g1621a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quire-ink" {...props}></Icon>
