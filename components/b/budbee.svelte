<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s44cpe4gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s44cpe4gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:budbee" {...props}></Icon>
