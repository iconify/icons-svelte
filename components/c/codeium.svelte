<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aieen2e4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aieen2e4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codeium" {...props}></Icon>
