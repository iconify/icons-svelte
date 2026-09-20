<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fugy1xbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fugy1xbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:align-top" {...props}></Icon>
