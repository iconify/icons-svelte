<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk78tqloq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk78tqloq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:history-round" {...props}></Icon>
