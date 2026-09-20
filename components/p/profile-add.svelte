<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4t6dmbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4t6dmbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:profile-add" {...props}></Icon>
