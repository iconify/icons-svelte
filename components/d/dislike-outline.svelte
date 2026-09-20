<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myf3l1ujr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="myf3l1ujr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dislike-outline" {...props}></Icon>
