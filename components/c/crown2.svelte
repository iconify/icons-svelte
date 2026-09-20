<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlyf48e1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlyf48e1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crown2" {...props}></Icon>
