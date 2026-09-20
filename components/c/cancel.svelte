<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo9--sbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jo9--sbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:cancel" {...props}></Icon>
