<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kax5-cj7n.css';
import '../../css/h/hyllzobun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kax5-cj7n"/><path clip-rule="evenodd" class="hyllzobun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:drama-filled" {...props}></Icon>
