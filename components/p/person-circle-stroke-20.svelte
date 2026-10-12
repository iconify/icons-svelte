<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngyvkq8lm.css';
import '../../css/b/b5it182ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ngyvkq8lm"/><path class="b5it182ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-circle-stroke-20" {...props}></Icon>
