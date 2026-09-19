<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf8xy5bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf8xy5bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-code-filled" {...props}></Icon>
