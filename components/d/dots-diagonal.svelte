<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-8zq7ywg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-8zq7ywg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dots-diagonal" {...props}></Icon>
