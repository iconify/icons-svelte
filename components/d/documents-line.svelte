<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py38cvbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py38cvbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:documents-line" {...props}></Icon>
