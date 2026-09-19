<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8nipv_he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e8nipv_he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-circle" {...props}></Icon>
