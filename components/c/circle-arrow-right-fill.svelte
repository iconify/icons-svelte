<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0n3fkbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0n3fkbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-right-fill" {...props}></Icon>
