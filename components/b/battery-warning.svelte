<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe_tb04fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe_tb04fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery-warning" {...props}></Icon>
