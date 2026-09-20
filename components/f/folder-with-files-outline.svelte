<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brzmvc2-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brzmvc2-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-with-files-outline" {...props}></Icon>
