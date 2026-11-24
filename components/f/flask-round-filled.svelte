<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_duhuwxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_duhuwxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flask-round-filled" {...props}></Icon>
