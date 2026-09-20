<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mamr9hpmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="mamr9hpmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:innowatio-logo" {...props}></Icon>
