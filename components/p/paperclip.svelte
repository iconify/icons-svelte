<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltu75mm9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltu75mm9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:paperclip" {...props}></Icon>
