<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9asq1fvt.css';
import '../../css/l/l4t7dwu3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9asq1fvt"/><path class="l4t7dwu3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-bold-duotone" {...props}></Icon>
