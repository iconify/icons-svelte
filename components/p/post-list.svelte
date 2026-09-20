<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqzg15b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="uqzg15b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:post-list" {...props}></Icon>
