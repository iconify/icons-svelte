<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6l4a7btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x6l4a7btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-up-left-light" {...props}></Icon>
