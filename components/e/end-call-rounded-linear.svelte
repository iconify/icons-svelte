<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8sx1wb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8sx1wb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-rounded-linear" {...props}></Icon>
