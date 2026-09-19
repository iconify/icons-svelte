<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krz0u-imm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krz0u-imm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:no-waiting-sign" {...props}></Icon>
