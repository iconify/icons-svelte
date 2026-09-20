<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb-_z3bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb-_z3bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-alert-outline" {...props}></Icon>
