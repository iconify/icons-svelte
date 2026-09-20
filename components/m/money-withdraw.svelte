<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtcj7q16c.css';
import '../../css/y/yn4943o-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wtcj7q16c"/><path class="yn4943o-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:money-withdraw" {...props}></Icon>
