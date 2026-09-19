<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7qt11bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7qt11bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:calendar" {...props}></Icon>
