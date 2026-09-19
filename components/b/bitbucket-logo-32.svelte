<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2r13mb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s2r13mb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bitbucket-logo-32" {...props}></Icon>
