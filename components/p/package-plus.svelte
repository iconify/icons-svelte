<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfo6uib_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfo6uib_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-plus" {...props}></Icon>
