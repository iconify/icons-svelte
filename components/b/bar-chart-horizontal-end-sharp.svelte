<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9uem0hua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9uem0hua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-horizontal-end-sharp" {...props}></Icon>
