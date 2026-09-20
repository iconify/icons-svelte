<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrtjxtb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrtjxtb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:binocular-bold" {...props}></Icon>
