<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhf9lobed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="uhf9lobed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hryvniasquare" {...props}></Icon>
