<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k42fv8bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k42fv8bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pen-off-filled" {...props}></Icon>
