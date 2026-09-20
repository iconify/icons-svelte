<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_eo4xb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_eo4xb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lerna" {...props}></Icon>
