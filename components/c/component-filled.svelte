<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uic_s0kyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uic_s0kyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:component-filled" {...props}></Icon>
