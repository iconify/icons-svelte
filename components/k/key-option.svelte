<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo_vvnwuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo_vvnwuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:key-option" {...props}></Icon>
