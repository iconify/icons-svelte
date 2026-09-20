<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6t5hcbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6t5hcbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:help-square-filled" {...props}></Icon>
