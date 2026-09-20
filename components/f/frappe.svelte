<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6u4_b-mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6u4_b-mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:frappe" {...props}></Icon>
