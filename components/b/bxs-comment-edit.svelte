<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhbfye42t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhbfye42t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-comment-edit" {...props}></Icon>
