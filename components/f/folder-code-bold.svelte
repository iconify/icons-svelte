<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4tso7b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4tso7b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-code-bold" {...props}></Icon>
