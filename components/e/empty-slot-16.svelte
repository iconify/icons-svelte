<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojruu7w3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ojruu7w3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:empty-slot-16" {...props}></Icon>
