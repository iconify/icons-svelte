<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kudu1-8ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kudu1-8ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:grow" {...props}></Icon>
