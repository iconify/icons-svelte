<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8qxi56ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8qxi56ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notes2" {...props}></Icon>
