<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwyic9box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwyic9box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:expand-vertical-duotone" {...props}></Icon>
