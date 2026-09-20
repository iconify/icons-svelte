<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ao1cc5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ao1cc5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-add-outline" {...props}></Icon>
