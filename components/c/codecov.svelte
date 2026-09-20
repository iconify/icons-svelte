<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh9fembrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh9fembrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codecov" {...props}></Icon>
