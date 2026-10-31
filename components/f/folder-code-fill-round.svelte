<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac36-yj6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac36-yj6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-code-fill-round" {...props}></Icon>
