<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9e3_dbsz.css';
import '../../css/b/b31iesblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9e3_dbsz"/><path class="b31iesblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-minus-filled" {...props}></Icon>
