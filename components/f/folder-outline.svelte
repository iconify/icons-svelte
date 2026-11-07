<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7z-uyzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy7z-uyzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-outline" {...props}></Icon>
