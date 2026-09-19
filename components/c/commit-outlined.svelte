<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6kkc4bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6kkc4bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:commit-outlined" {...props}></Icon>
