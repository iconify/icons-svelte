<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw6az9bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw6az9bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-jpg" {...props}></Icon>
