<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb1v_judf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb1v_judf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:git-commit-horizontal" {...props}></Icon>
