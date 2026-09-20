<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyzb7jb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyzb7jb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bruno" {...props}></Icon>
