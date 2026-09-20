<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggd0kfbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ggd0kfbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:plus-square" {...props}></Icon>
