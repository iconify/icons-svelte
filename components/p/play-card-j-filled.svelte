<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh3gl-b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh3gl-b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-j-filled" {...props}></Icon>
