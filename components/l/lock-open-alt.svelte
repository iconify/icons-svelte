<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wabuv5b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wabuv5b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:lock-open-alt" {...props}></Icon>
