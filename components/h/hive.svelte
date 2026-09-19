<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irp05ubzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irp05ubzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hive" {...props}></Icon>
