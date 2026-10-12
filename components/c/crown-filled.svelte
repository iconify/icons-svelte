<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya6puy14o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya6puy14o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:crown-filled" {...props}></Icon>
