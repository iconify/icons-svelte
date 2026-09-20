<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyd11u1lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyd11u1lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:check-circle-solid" {...props}></Icon>
