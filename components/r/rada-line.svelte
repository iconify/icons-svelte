<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaqsa0buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaqsa0buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rada-line" {...props}></Icon>
