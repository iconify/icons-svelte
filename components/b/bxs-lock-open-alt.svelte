<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq0bqacml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq0bqacml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-lock-open-alt" {...props}></Icon>
