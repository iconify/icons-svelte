<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el5c7fldi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="el5c7fldi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-upload" {...props}></Icon>
