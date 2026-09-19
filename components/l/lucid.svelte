<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-cmhy-ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-cmhy-ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lucid" {...props}></Icon>
