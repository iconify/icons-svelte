<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcre68axd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcre68axd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:check-list-filled" {...props}></Icon>
