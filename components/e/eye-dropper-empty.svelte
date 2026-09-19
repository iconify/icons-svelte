<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9v9tbc3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t9v9tbc3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:eye-dropper-empty" {...props}></Icon>
