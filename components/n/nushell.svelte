<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id6zxua6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id6zxua6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nushell" {...props}></Icon>
