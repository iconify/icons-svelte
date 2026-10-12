<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpcj9efqn.css';
import '../../css/s/s9lr0vb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpcj9efqn"/><path class="s9lr0vb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:caravan-filled" {...props}></Icon>
