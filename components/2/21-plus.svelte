<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evwgfru8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evwgfru8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:21-plus" {...props}></Icon>
