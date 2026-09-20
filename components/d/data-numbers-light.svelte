<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo453mk3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jo453mk3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-numbers-light" {...props}></Icon>
