<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tasb54b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tasb54b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:key-alt-back" {...props}></Icon>
