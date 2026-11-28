<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr0-7kx7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr0-7kx7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-check-solid" {...props}></Icon>
