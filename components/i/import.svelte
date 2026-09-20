<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czhzwvb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="czhzwvb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:import" {...props}></Icon>
