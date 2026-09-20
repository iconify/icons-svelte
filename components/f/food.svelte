<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng4ff_p6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng4ff_p6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:food" {...props}></Icon>
