<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwkbm-b6b.css';
import '../../css/i/ivt8o-bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwkbm-b6b"/><path class="ivt8o-bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:book-add" {...props}></Icon>
