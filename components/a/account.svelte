<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a83n9zpmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a83n9zpmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:account" {...props}></Icon>
