<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx7ywibap.css';
import '../../css/l/l7g6jsgpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx7ywibap"/><path clip-rule="evenodd" class="l7g6jsgpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-bottom-close-filled" {...props}></Icon>
