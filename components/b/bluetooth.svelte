<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htfk-0bug.css';
import '../../css/u/u_em3xrxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htfk-0bug"/><path class="u_em3xrxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:bluetooth" {...props}></Icon>
