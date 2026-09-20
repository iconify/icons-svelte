<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz8hf6bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz8hf6bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-check-outline" {...props}></Icon>
