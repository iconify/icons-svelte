<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aosgu1bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aosgu1bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:equal-triple" {...props}></Icon>
