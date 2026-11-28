<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f87tu5f-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f87tu5f-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:lock-check" {...props}></Icon>
