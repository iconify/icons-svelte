<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6v241bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c6v241bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-bin-fill" {...props}></Icon>
