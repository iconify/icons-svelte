<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8rw6-4fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8rw6-4fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:humblebundle" {...props}></Icon>
