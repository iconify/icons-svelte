<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il0b9_6at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="il0b9_6at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:folder-open-o" {...props}></Icon>
