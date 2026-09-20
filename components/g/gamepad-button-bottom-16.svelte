<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdnb4ibza.css';
import '../../css/v/va7yy6tym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fdnb4ibza"/><path class="va7yy6tym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-button-bottom-16" {...props}></Icon>
