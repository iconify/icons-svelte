<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt6fu6oeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rt6fu6oeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-audio-fill" {...props}></Icon>
