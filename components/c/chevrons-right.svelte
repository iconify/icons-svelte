<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-mbilwso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o-mbilwso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:chevrons-right" {...props}></Icon>
