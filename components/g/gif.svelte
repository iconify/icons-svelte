<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bslrgc91y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bslrgc91y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:gif" {...props}></Icon>
