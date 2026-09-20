<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asoryimij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asoryimij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:folder-delete" {...props}></Icon>
