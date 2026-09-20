<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlp3f3bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rlp3f3bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rope-fence" {...props}></Icon>
