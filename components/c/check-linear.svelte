<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klaz9acmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klaz9acmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-linear" {...props}></Icon>
