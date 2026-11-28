<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxwv_6pot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yxwv_6pot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mountain-duotone" {...props}></Icon>
