<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul_2399ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul_2399ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:plesk" {...props}></Icon>
