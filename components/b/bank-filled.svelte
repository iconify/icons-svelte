<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jem20x6hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jem20x6hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bank-filled" {...props}></Icon>
