<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul4ei0bva.css';
import '../../css/s/sqg9nvbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4ei0bva"/><path class="sqg9nvbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mobile-back" {...props}></Icon>
