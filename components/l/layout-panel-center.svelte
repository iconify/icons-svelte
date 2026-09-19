<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jne2jabmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jne2jabmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-panel-center" {...props}></Icon>
