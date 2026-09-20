<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6l8xqbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6l8xqbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note3-filled" {...props}></Icon>
