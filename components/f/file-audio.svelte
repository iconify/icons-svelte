<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brpcrsbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brpcrsbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:file-audio" {...props}></Icon>
