<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9jtn9bji.css';
import '../../css/j/j5hqbks0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9jtn9bji"/><path class="j5hqbks0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:circle" {...props}></Icon>
