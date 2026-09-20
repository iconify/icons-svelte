<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-5rdijtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-5rdijtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lightning-off-solid" {...props}></Icon>
