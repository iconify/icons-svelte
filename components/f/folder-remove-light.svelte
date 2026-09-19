<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1wicobvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1wicobvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-remove-light" {...props}></Icon>
