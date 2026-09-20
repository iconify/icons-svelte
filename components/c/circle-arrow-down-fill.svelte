<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t16izkbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t16izkbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-down-fill" {...props}></Icon>
