<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4kl7kb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4kl7kb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bone-bulk-round" {...props}></Icon>
