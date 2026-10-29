<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j21j9ab8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j21j9ab8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gem-solid" {...props}></Icon>
