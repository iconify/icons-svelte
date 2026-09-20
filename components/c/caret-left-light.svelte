<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v88syb4jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v88syb4jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:caret-left-light" {...props}></Icon>
