<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb9q0o-di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb9q0o-di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:double-arrow-circle-fill" {...props}></Icon>
