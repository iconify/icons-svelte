<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf-pqzgog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf-pqzgog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-fading-plus-solid" {...props}></Icon>
