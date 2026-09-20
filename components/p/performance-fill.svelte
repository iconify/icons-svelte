<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqftaosoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dqftaosoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:performance-fill" {...props}></Icon>
