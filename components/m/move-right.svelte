<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c86_q-b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c86_q-b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:move-right" {...props}></Icon>
