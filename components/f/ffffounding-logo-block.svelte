<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phd1g1bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phd1g1bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ffffounding-logo-block" {...props}></Icon>
