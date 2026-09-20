<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b62_42brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b62_42brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bold" {...props}></Icon>
