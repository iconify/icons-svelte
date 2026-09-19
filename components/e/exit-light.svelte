<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zavdn0vkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zavdn0vkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:exit-light" {...props}></Icon>
