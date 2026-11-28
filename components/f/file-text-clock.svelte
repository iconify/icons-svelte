<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5jyj5bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5jyj5bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-text-clock" {...props}></Icon>
