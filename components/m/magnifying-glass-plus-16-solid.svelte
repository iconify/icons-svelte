<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmjeu90su.css';
import '../../css/j/j7-kr4q1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hmjeu90su"/><path clip-rule="evenodd" class="j7-kr4q1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-plus-16-solid" {...props}></Icon>
