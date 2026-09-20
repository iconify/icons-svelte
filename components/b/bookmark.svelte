<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on_4e8bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on_4e8bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark" {...props}></Icon>
