<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo5oq8bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo5oq8bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diary-fill" {...props}></Icon>
