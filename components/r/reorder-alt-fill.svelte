<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b20sknb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b20sknb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:reorder-alt-fill" {...props}></Icon>
