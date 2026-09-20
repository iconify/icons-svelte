<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8krip7dh.css';
import '../../css/y/yapqosbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8krip7dh"/><path class="yapqosbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:archive" {...props}></Icon>
