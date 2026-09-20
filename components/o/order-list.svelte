<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msydp5vzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msydp5vzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:order-list" {...props}></Icon>
