<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wllbo2bcu.css';
import '../../css/g/ge98ujwjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wllbo2bcu"/><path class="ge98ujwjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-minus-filled" {...props}></Icon>
