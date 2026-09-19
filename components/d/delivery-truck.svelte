<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs_ds4bwb.css';
import '../../css/t/t1tvrdn3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs_ds4bwb"/><path class="t1tvrdn3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:delivery-truck" {...props}></Icon>
