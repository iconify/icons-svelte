<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upc9h7bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upc9h7bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen-edit-circle-alt-filled" {...props}></Icon>
