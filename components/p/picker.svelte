<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq_h_l3hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sq_h_l3hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:picker" {...props}></Icon>
