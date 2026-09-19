<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-13sr1wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-13sr1wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mustang" {...props}></Icon>
