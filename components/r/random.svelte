<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi0lwub-e.css';
import '../../css/e/eekz3efxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vi0lwub-e"/><path class="eekz3efxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:random" {...props}></Icon>
