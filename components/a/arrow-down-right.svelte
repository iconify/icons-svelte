<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivgtwjvek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivgtwjvek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-down-right" {...props}></Icon>
