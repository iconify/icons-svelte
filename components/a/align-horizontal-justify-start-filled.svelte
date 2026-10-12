<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r83azcbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r83azcbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-justify-start-filled" {...props}></Icon>
