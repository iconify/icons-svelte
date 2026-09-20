<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v819m1itl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v819m1itl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-git-bold" {...props}></Icon>
