<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4yqmhbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v4yqmhbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:railway-track-partial" {...props}></Icon>
