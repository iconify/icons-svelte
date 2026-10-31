<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezpr1gb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezpr1gb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:puzzle-round" {...props}></Icon>
