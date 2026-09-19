<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbd0fnbds.css';
import '../../css/s/sk6tzx05l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbd0fnbds"/><path class="sk6tzx05l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:computer-retro" {...props}></Icon>
