<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz9iuq2bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hz9iuq2bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:lifebuoy" {...props}></Icon>
