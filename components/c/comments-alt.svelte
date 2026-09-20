<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6n0u6b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6n0u6b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comments-alt" {...props}></Icon>
