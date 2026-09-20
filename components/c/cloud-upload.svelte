<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2xcm6bdm.css';
import '../../css/j/j11lf1bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2xcm6bdm"/><path class="j11lf1bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-upload" {...props}></Icon>
