<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiyuxlwou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eiyuxlwou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:help-hexagon-filled" {...props}></Icon>
