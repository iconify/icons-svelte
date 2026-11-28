<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5d-p4yqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5d-p4yqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:notebook-edit" {...props}></Icon>
