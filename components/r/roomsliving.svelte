<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1cisd-qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1cisd-qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roomsliving" {...props}></Icon>
