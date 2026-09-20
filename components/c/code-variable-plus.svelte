<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1xknzbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1xknzbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:code-variable-plus" {...props}></Icon>
