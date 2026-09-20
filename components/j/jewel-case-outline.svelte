<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1zff1uym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1zff1uym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:jewel-case-outline" {...props}></Icon>
