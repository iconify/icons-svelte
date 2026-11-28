<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipdjeevco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipdjeevco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:balloon" {...props}></Icon>
