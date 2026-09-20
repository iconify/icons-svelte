<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l89i7ubhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l89i7ubhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fruit-grapes" {...props}></Icon>
