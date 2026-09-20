<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkqg3otwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkqg3otwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-haskell" {...props}></Icon>
