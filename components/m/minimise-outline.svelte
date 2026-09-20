<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohi4kqh9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ohi4kqh9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:minimise-outline" {...props}></Icon>
