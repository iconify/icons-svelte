<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix2_4ebjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ix2_4ebjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-file-fill" {...props}></Icon>
