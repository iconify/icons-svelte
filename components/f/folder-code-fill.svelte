<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frqg3oa9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frqg3oa9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-code-fill" {...props}></Icon>
