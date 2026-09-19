<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ers4h5bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ers4h5bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-kallax4" {...props}></Icon>
