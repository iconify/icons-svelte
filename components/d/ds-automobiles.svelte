<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpvie97gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpvie97gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ds-automobiles" {...props}></Icon>
