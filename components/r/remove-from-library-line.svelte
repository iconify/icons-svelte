<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldk6ger7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldk6ger7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:remove-from-library-line" {...props}></Icon>
