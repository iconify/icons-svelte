<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8sn5607z.css';
import '../../css/p/puqsb9b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8sn5607z"/><path class="puqsb9b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-open-filled" {...props}></Icon>
