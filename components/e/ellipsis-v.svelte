<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7v99r1ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7v99r1ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:ellipsis-v" {...props}></Icon>
