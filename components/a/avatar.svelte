<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4pew8t4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z4pew8t4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:avatar" {...props}></Icon>
