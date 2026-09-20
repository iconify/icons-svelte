<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa0-u8b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa0-u8b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nicehash" {...props}></Icon>
