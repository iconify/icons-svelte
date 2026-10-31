<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y44_4jbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y44_4jbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:asterisk-bulk-round" {...props}></Icon>
