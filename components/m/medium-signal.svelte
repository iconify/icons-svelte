<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c07fxkbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c07fxkbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:medium-signal" {...props}></Icon>
