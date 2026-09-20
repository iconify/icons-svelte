<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujunp-b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujunp-b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:between-horizontal-start" {...props}></Icon>
