<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqymm9brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqymm9brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:folder-remove" {...props}></Icon>
