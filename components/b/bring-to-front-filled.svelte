<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox6ac-bhz.css';
import '../../css/p/ps-9ixb8e.css';
import '../../css/o/oo9pv9z9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox6ac-bhz"/><path class="ps-9ixb8e"/><path class="oo9pv9z9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bring-to-front-filled" {...props}></Icon>
