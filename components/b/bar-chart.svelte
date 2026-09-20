<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clmtl9q-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-4};
const content = `<path class="clmtl9q-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bar-chart" {...props}></Icon>
