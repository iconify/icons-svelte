<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hewys-vhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hewys-vhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:chevron-lg-left" {...props}></Icon>
