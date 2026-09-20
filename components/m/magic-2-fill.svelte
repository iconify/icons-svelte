<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sln1u9bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sln1u9bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-2-fill" {...props}></Icon>
