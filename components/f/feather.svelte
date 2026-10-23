<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojh5zlf0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojh5zlf0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:feather" {...props}></Icon>
