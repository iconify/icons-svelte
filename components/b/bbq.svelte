<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac_7zloqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ac_7zloqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bbq" {...props}></Icon>
