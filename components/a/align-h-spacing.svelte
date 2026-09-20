<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc0oi5fkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kc0oi5fkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-h-spacing" {...props}></Icon>
