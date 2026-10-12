<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe9kskltn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe9kskltn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:group-filled" {...props}></Icon>
