<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3-mg25mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3-mg25mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:monitor-filled" {...props}></Icon>
