<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw7m7766j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw7m7766j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-narrow-up" {...props}></Icon>
