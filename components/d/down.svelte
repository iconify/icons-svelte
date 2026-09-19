<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz-t35b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":392,"height":448};
const content = `<path class="sz-t35b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:down" {...props}></Icon>
