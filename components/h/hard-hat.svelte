<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aotw6rd9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aotw6rd9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hard-hat" {...props}></Icon>
