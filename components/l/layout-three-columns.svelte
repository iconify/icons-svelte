<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb9dqsb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nb9dqsb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:layout-three-columns" {...props}></Icon>
