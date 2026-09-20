<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh96-wwdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh96-wwdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:blessing-fill" {...props}></Icon>
