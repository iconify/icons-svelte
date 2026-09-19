<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oebpepj7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oebpepj7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:edit" {...props}></Icon>
