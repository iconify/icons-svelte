<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx4o6tq-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx4o6tq-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:car-sharp" {...props}></Icon>
