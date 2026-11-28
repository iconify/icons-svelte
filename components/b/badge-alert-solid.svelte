<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b26zaqbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b26zaqbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-alert-solid" {...props}></Icon>
