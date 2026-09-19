<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vex7ouxjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vex7ouxjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookshelf-02" {...props}></Icon>
