<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozrj7jdhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ozrj7jdhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:jigsaw-piece" {...props}></Icon>
