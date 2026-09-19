<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcq4w6wrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fcq4w6wrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cloud-outline" {...props}></Icon>
