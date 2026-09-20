<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awy-u70-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awy-u70-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opentui" {...props}></Icon>
