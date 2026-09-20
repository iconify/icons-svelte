<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laizaxi8c.css';
import '../../css/q/q74t5xb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laizaxi8c"/><path class="q74t5xb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:align" {...props}></Icon>
