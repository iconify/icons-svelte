<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k36-ezbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k36-ezbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:outdent-solid" {...props}></Icon>
