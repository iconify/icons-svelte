<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kba0yde4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kba0yde4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-fill" {...props}></Icon>
