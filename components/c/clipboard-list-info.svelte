<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax5h1hb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax5h1hb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-list-info" {...props}></Icon>
