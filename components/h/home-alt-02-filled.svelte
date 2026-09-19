<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_qnqib-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_qnqib-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:home-alt-02-filled" {...props}></Icon>
