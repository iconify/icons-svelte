<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grh95ibtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grh95ibtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:reward-stars-4-bold" {...props}></Icon>
