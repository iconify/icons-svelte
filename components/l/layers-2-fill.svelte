<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldbsrwxzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldbsrwxzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layers-2-fill" {...props}></Icon>
