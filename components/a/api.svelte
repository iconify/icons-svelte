<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijk9gbbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ijk9gbbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:api" {...props}></Icon>
