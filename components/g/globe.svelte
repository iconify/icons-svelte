<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2v_ogb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2v_ogb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:globe" {...props}></Icon>
