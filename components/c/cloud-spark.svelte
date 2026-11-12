<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1nxg7bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1nxg7bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-spark" {...props}></Icon>
