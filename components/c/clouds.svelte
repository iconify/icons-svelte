<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8ojobqph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8ojobqph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clouds" {...props}></Icon>
