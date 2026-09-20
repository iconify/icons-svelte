<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhrz6z-de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhrz6z-de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:book-bookmark2" {...props}></Icon>
