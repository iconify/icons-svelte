<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s03-lacgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s03-lacgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-paper-line" {...props}></Icon>
