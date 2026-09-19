<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqxjixmrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqxjixmrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:off-close" {...props}></Icon>
