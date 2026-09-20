<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftjntstdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftjntstdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:carabiner" {...props}></Icon>
