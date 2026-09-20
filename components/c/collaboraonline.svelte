<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br-3rw75n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br-3rw75n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:collaboraonline" {...props}></Icon>
