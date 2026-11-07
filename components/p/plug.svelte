<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it57tnbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it57tnbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:plug" {...props}></Icon>
