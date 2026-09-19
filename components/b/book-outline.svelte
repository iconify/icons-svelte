<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_8h8ijtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_8h8ijtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:book-outline" {...props}></Icon>
