<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iadv0h46r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iadv0h46r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:angle-down" {...props}></Icon>
