<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8y4vab0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8y4vab0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:euro" {...props}></Icon>
