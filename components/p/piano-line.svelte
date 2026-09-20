<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr0kq8bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr0kq8bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:piano-line" {...props}></Icon>
