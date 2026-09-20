<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2e_5bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb2e_5bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:minimize-2" {...props}></Icon>
