<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgk3xum5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgk3xum5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-plus" {...props}></Icon>
