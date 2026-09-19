<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg087rbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg087rbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cpu" {...props}></Icon>
