<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhdsewb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jhdsewb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:retry" {...props}></Icon>
