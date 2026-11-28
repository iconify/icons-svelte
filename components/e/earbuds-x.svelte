<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/turzsbbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="turzsbbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:earbuds-x" {...props}></Icon>
