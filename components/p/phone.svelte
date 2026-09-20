<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-b21jb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-b21jb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:phone" {...props}></Icon>
