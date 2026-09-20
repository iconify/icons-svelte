<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agc2edjjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agc2edjjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-west" {...props}></Icon>
