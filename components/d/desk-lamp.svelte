<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqvw-cb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqvw-cb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:desk-lamp" {...props}></Icon>
