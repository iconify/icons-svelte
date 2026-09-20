<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3ja3ib0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="u3ja3ib0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:inbox" {...props}></Icon>
