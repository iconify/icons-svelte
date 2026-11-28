<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtrqm0byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtrqm0byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-two-solid" {...props}></Icon>
