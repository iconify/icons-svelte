<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhd2yph4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhd2yph4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-steps-filled" {...props}></Icon>
