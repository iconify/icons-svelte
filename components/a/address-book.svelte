<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz7nwdbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jz7nwdbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:address-book" {...props}></Icon>
