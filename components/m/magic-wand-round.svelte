<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eotd31bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eotd31bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:magic-wand-round" {...props}></Icon>
