<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsq2kbeni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsq2kbeni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-put" {...props}></Icon>
