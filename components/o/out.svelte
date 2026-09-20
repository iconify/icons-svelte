<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o27r778ow.css';
import '../../css/i/iq9a7xo1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o27r778ow"/><path class="iq9a7xo1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:out" {...props}></Icon>
