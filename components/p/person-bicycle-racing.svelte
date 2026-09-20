<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b69k8vrkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b69k8vrkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-bicycle-racing" {...props}></Icon>
