<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8t0y_b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g8t0y_b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:inbox-16" {...props}></Icon>
