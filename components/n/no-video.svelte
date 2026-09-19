<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-dd5ubvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-dd5ubvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-video" {...props}></Icon>
