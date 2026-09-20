<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x30hg2b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x30hg2b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heart-fill" {...props}></Icon>
