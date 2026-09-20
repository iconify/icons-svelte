<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu1ua8bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu1ua8bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:curseforge" {...props}></Icon>
