<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh2vge6it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh2vge6it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dna-filled" {...props}></Icon>
