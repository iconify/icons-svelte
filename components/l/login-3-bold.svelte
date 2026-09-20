<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqcf1z8cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eqcf1z8cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-3-bold" {...props}></Icon>
