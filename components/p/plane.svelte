<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkb7qk5lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkb7qk5lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plane" {...props}></Icon>
