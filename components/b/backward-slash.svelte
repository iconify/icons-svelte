<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpon2rbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpon2rbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:backward-slash" {...props}></Icon>
