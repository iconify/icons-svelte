<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvo6zwbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvo6zwbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil-minus-outline" {...props}></Icon>
