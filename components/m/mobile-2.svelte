<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj0nwob6o.css';
import '../../css/d/dake0_b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="nj0nwob6o"/><path class="dake0_b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:mobile-2" {...props}></Icon>
