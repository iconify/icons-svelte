<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huh-o7buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":819,"height":636};
const content = `<path class="huh-o7buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:readability" {...props}></Icon>
