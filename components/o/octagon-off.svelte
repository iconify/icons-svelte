<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4215uq9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4215uq9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-off" {...props}></Icon>
