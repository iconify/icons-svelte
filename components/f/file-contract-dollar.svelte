<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6yug67vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6yug67vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-contract-dollar" {...props}></Icon>
