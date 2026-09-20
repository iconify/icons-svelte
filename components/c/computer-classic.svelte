<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs66gybrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs66gybrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:computer-classic" {...props}></Icon>
