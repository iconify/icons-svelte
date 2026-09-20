<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f07w5edil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f07w5edil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-bar" {...props}></Icon>
