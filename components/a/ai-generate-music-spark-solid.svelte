<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at-x-4buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="at-x-4buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-generate-music-spark-solid" {...props}></Icon>
