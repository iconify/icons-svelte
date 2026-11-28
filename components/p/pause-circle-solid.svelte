<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8z71kbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8z71kbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pause-circle-solid" {...props}></Icon>
