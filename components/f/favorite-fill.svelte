<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psjehab6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psjehab6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:favorite-fill" {...props}></Icon>
