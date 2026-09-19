<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uctwj4buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uctwj4buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flag-01" {...props}></Icon>
