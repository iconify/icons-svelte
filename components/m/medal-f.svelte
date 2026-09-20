<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugymjwbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1};
const content = `<path class="ugymjwbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:medal-f" {...props}></Icon>
