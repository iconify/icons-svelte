<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyl9qceen.css';
import '../../css/k/k02-v4bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyl9qceen"/><path class="k02-v4bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:badge-check" {...props}></Icon>
