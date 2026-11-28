<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o24kj0b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o24kj0b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chocolate-bar-solid" {...props}></Icon>
