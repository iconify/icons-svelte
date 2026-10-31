<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b73s-ci7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b73s-ci7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-double-left-round" {...props}></Icon>
