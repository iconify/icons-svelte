<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bck43kbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bck43kbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:discotheque" {...props}></Icon>
