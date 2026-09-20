<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8vmp6bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8vmp6bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-downward-square-line" {...props}></Icon>
