<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obz4hac9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obz4hac9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-right-filled" {...props}></Icon>
