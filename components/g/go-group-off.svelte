<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orkd00b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orkd00b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:go-group-off" {...props}></Icon>
