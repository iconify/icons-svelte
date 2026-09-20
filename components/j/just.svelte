<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2qkqacya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2qkqacya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:just" {...props}></Icon>
