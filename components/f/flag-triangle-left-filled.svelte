<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6625acdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6625acdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flag-triangle-left-filled" {...props}></Icon>
