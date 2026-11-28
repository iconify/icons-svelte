<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii--4nbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii--4nbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-text-check" {...props}></Icon>
