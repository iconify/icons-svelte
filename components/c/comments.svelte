<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2zvx5bln.css';
import '../../css/b/b3h4d4bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h2zvx5bln"/><path class="b3h4d4bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:comments" {...props}></Icon>
