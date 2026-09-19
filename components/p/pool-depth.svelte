<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-mx6rb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-mx6rb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pool-depth" {...props}></Icon>
