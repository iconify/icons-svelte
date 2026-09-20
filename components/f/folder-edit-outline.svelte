<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vue9vbuek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vue9vbuek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-edit-outline" {...props}></Icon>
