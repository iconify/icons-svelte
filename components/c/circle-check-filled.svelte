<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e65egtbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e65egtbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-check-filled" {...props}></Icon>
