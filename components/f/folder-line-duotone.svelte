<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juolcjavn.css';
import '../../css/i/i4kly5b8q.css';
import '../../css/l/laly9hbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juolcjavn"/><path class="i4kly5b8q"/><path class="laly9hbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-line-duotone" {...props}></Icon>
