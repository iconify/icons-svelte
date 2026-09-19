<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpv-qub9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpv-qub9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:font-color" {...props}></Icon>
