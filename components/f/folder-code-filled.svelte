<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0cemnzaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0cemnzaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder-code-filled" {...props}></Icon>
