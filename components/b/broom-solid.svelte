<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if87crbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if87crbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:broom-solid" {...props}></Icon>
