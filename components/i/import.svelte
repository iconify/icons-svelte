<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2q3-9bye.css';
import '../../css/z/zbzhdcacm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2q3-9bye"/><path class="zbzhdcacm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:import" {...props}></Icon>
