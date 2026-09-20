<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk5lknkay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk5lknkay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabetical-variant-off" {...props}></Icon>
