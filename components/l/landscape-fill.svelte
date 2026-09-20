<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghq6p89ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghq6p89ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:landscape-fill" {...props}></Icon>
