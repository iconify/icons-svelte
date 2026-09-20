<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwpq41q1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwpq41q1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-no-axes-combined" {...props}></Icon>
