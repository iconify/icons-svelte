<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqopl_b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqopl_b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:powerpages" {...props}></Icon>
