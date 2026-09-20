<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6jc4kd1z.css';
import '../../css/b/bikjexb7g.css';
import '../../css/j/j_8h5jbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q6jc4kd1z"/><path class="bikjexb7g"/><path class="j_8h5jbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:margin" {...props}></Icon>
