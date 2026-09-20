<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgfbc-ifb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgfbc-ifb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-dublicate-fill" {...props}></Icon>
