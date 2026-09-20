<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-bp9fvll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-bp9fvll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bin" {...props}></Icon>
