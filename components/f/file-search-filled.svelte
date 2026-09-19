<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm9levbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vm9levbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-search-filled" {...props}></Icon>
