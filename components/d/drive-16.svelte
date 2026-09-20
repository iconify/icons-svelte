<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz9r51iha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nz9r51iha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:drive-16" {...props}></Icon>
