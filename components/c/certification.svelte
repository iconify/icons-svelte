<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3_-5is-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3_-5is-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:certification" {...props}></Icon>
