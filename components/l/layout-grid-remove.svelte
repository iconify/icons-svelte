<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3tnx-bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3tnx-bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-grid-remove" {...props}></Icon>
