<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8yv7ccwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8yv7ccwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:antlr" {...props}></Icon>
