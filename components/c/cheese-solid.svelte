<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqk4_wbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqk4_wbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cheese-solid" {...props}></Icon>
