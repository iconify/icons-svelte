<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzny-seit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzny-seit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:arrow-circle-left" {...props}></Icon>
