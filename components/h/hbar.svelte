<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk6zr-wff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk6zr-wff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hbar" {...props}></Icon>
