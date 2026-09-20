<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziaa1cqwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziaa1cqwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:code-blocks" {...props}></Icon>
