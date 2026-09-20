<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wui9vd-9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="wui9vd-9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:mountain" {...props}></Icon>
