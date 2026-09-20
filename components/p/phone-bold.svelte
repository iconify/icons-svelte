<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx43in0lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx43in0lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-bold" {...props}></Icon>
