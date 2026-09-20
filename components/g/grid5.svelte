<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r68q1bzjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r68q1bzjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid5" {...props}></Icon>
