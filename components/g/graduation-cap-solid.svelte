<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mysg7cy2i.css';
import '../../css/j/juxl4d1ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mysg7cy2i"/><path class="juxl4d1ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:graduation-cap-solid" {...props}></Icon>
