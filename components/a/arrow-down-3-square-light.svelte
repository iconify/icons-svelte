<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7v35776a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7v35776a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-3-square-light" {...props}></Icon>
