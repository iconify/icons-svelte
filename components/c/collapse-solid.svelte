<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7_4gwb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7_4gwb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:collapse-solid" {...props}></Icon>
