<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqdbx8b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqdbx8b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:activeloop" {...props}></Icon>
