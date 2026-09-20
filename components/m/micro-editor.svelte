<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqhpp2a5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqhpp2a5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:micro-editor" {...props}></Icon>
