<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eifwhrbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eifwhrbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:inbox-fill-24" {...props}></Icon>
