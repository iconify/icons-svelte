<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6rz7f3rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r6rz7f3rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:incognito" {...props}></Icon>
