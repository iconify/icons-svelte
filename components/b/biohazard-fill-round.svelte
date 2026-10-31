<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea74grkel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea74grkel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:biohazard-fill-round" {...props}></Icon>
