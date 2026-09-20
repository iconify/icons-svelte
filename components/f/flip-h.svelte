<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw9m35gro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw9m35gro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:flip-h" {...props}></Icon>
