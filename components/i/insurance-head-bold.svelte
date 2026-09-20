<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb3enpbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb3enpbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:insurance-head-bold" {...props}></Icon>
