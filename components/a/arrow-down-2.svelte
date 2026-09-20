<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_zndpbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zndpbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-down-2" {...props}></Icon>
