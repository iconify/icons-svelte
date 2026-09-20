<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqgn4zb9y.css';
import '../../css/i/i2zu83iwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cqgn4zb9y"/><path class="i2zu83iwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fwb" {...props}></Icon>
