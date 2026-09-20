<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt2id7bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt2id7bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:aperture-off" {...props}></Icon>
