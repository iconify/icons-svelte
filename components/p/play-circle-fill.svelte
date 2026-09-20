<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m49rw4yqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m49rw4yqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:play-circle-fill" {...props}></Icon>
