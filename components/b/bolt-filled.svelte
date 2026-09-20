<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-qn9i21d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-qn9i21d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bolt-filled" {...props}></Icon>
