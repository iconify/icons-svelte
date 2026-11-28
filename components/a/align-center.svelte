<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ge2ibcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ge2ibcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:align-center" {...props}></Icon>
