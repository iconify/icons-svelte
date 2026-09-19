<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9k84bc7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="t9k84bc7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:city" {...props}></Icon>
