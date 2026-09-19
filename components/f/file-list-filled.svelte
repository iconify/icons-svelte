<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7bd_7bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7bd_7bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-list-filled" {...props}></Icon>
