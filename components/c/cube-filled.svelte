<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9a5m2bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9a5m2bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cube-filled" {...props}></Icon>
