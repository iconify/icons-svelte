<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av8mzqlfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av8mzqlfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:plane-departure-solid" {...props}></Icon>
