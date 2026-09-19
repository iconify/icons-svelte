<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcibvrb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcibvrb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cable-car" {...props}></Icon>
