<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k41ar9pyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k41ar9pyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-4-solid" {...props}></Icon>
