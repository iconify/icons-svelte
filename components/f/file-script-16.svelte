<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oswg-4fqg.css';
import '../../css/e/eqbv84bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oswg-4fqg"/><path clip-rule="evenodd" class="eqbv84bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:file-script-16" {...props}></Icon>
