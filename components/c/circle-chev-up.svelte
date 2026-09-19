<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqc3elbeh.css';
import '../../css/i/ih5nivq9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqc3elbeh"/><path class="ih5nivq9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-chev-up" {...props}></Icon>
