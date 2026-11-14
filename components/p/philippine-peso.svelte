<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efng8jwqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efng8jwqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:philippine-peso" {...props}></Icon>
