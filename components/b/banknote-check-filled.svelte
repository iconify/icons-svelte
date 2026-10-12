<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-wke7znd.css';
import '../../css/p/p1xhgbied.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-wke7znd"/><path clip-rule="evenodd" class="p1xhgbied"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:banknote-check-filled" {...props}></Icon>
