<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go7qv8fna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go7qv8fna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-turbocharger" {...props}></Icon>
