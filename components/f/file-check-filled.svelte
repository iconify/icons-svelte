<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc_-wh9rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc_-wh9rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-check-filled" {...props}></Icon>
