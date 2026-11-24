<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ud-hb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7ud-hb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:astroid-filled" {...props}></Icon>
