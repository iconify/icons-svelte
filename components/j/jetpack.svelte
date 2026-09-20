<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-rj56b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-rj56b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:jetpack" {...props}></Icon>
