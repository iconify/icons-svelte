<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8g-9jb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8g-9jb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pen-line" {...props}></Icon>
