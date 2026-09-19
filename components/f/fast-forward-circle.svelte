<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya6h9sbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya6h9sbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:fast-forward-circle" {...props}></Icon>
