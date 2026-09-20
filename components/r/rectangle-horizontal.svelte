<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua6jnvbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="ua6jnvbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:rectangle-horizontal" {...props}></Icon>
