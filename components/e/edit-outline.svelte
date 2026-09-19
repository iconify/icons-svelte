<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi1kkcb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi1kkcb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:edit-outline" {...props}></Icon>
