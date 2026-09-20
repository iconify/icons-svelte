<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spajzybyt.css';
import '../../css/t/t_5urzb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spajzybyt"/><path class="t_5urzb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-template" {...props}></Icon>
