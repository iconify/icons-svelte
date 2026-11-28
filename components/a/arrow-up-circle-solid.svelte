<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uchy9pbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uchy9pbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-circle-solid" {...props}></Icon>
