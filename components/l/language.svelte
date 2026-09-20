<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot0t-9mok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot0t-9mok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:language" {...props}></Icon>
