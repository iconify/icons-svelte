<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mro7kxbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mro7kxbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:angle-left" {...props}></Icon>
