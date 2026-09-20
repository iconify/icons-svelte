<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcb4e8b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bcb4e8b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-beside-person-above-sedan" {...props}></Icon>
