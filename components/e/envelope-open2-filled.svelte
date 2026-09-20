<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtk1hdbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qtk1hdbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:envelope-open2-filled" {...props}></Icon>
