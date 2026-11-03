<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1p2nbbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1p2nbbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-edit" {...props}></Icon>
