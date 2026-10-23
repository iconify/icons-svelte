<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqg1e6ggw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqg1e6ggw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bacon-filled" {...props}></Icon>
