<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbgir05ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgir05ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dice-3-filled" {...props}></Icon>
