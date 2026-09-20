<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93i6piec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o93i6piec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jouav" {...props}></Icon>
