<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy6wwtboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy6wwtboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-check" {...props}></Icon>
