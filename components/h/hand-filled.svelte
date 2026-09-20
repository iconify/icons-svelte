<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjq9yqxug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjq9yqxug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hand-filled" {...props}></Icon>
