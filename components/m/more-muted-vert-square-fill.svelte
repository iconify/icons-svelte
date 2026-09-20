<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyzt3kbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nyzt3kbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-muted-vert-square-fill" {...props}></Icon>
