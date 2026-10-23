<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i58ybmb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i58ybmb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:external-link" {...props}></Icon>
