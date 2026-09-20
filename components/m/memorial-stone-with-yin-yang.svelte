<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hptsw6dqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hptsw6dqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:memorial-stone-with-yin-yang" {...props}></Icon>
