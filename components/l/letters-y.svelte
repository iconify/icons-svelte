<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr6bb7e4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr6bb7e4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-y" {...props}></Icon>
