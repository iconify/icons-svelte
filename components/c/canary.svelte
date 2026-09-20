<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul96qtblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul96qtblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:canary" {...props}></Icon>
