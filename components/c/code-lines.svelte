<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ali6sre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-ali6sre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:code-lines" {...props}></Icon>
