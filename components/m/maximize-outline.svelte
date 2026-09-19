<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm30exbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm30exbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:maximize-outline" {...props}></Icon>
