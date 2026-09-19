<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyrpwqb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyrpwqb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:calendar" {...props}></Icon>
