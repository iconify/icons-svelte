<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8l-jmhst.css';
import '../../css/v/vqw6mobct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8l-jmhst"/><path class="vqw6mobct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brush-filled" {...props}></Icon>
