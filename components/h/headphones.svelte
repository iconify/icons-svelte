<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b70adqb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b70adqb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:headphones" {...props}></Icon>
