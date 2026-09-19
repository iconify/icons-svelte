<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvj-_sb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="lvj-_sb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:firefox" {...props}></Icon>
