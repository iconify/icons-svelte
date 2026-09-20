<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqc81jp9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqc81jp9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ant" {...props}></Icon>
