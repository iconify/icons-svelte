<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq0szjbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pq0szjbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-check-outline" {...props}></Icon>
