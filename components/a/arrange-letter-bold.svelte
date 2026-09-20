<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8nqarbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8nqarbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrange-letter-bold" {...props}></Icon>
