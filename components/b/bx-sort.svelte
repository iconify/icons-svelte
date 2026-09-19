<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g64z6fbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g64z6fbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-sort" {...props}></Icon>
