<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgk9pubpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lgk9pubpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:epic-closed" {...props}></Icon>
