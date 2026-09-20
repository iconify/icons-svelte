<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc6v9sklm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc6v9sklm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:codesandbox" {...props}></Icon>
