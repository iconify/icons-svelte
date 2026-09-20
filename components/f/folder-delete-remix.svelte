<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sosc3bbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sosc3bbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:folder-delete-remix" {...props}></Icon>
