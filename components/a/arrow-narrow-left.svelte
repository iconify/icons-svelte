<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5umild4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5umild4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-narrow-left" {...props}></Icon>
