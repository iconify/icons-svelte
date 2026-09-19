<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrnekj3ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrnekj3ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-2-thin" {...props}></Icon>
