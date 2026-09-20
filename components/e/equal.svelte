<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv628ykgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv628ykgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:equal" {...props}></Icon>
