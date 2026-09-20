<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij1mjvbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij1mjvbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coolant-temperature" {...props}></Icon>
