<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1wd56y2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1wd56y2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:help" {...props}></Icon>
