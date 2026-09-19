<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igd0rpbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="igd0rpbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:pointer-left-fill" {...props}></Icon>
