<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spajzybyt.css';
import '../../css/h/hhwq3mbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spajzybyt"/><path class="hhwq3mbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-mock" {...props}></Icon>
