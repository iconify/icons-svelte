<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s43y9hb-k.css';
import '../../css/w/wqz8cobop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s43y9hb-k"/><path class="wqz8cobop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:detail" {...props}></Icon>
