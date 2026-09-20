<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u136l-8rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u136l-8rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-favorite-bookmark-outline" {...props}></Icon>
