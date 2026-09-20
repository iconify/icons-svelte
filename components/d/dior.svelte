<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sntvwqj6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sntvwqj6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dior" {...props}></Icon>
