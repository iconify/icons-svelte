<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyv9g8b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyv9g8b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-user-fill-round" {...props}></Icon>
