<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8tyo-b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8tyo-b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:first-aid" {...props}></Icon>
