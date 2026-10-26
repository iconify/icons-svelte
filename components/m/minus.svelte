<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6f6kcstl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y6f6kcstl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:minus" {...props}></Icon>
