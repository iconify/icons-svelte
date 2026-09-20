<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss1agp6sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss1agp6sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-alt-circle-left-solid" {...props}></Icon>
