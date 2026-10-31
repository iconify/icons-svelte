<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx2kf4bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx2kf4bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-pull-request-draft-fill-round" {...props}></Icon>
