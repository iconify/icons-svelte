<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2vtr0hjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2vtr0hjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-up-filled" {...props}></Icon>
