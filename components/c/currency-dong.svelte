<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnv2b63dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnv2b63dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-dong" {...props}></Icon>
