<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyg7nob9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyg7nob9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:information-circle-bold" {...props}></Icon>
