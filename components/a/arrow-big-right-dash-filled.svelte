<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amr7ppo4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amr7ppo4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:arrow-big-right-dash-filled" {...props}></Icon>
