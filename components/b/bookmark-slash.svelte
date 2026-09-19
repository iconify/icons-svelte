<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfjukmb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfjukmb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bookmark-slash" {...props}></Icon>
