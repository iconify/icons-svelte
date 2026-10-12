<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_1mwj-2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_1mwj-2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:pipeline" {...props}></Icon>
