<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4vr5yjnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4vr5yjnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-path-connect-outline" {...props}></Icon>
