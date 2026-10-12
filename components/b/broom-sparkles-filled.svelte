<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb7tk6biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb7tk6biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:broom-sparkles-filled" {...props}></Icon>
