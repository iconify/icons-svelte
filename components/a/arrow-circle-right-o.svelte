<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkd5oxl6c.css';
import '../../css/b/bc_ody0we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fkd5oxl6c"/><path class="bc_ody0we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-circle-right-o" {...props}></Icon>
