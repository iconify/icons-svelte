<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw24dqfdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw24dqfdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lodash" {...props}></Icon>
