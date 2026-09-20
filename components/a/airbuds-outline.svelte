<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8j-1-v7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8j-1-v7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-outline" {...props}></Icon>
