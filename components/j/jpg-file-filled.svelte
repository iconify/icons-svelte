<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e36ltbb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e36ltbb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:jpg-file-filled" {...props}></Icon>
