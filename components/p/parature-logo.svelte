<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df1l_fhyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="df1l_fhyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:parature-logo" {...props}></Icon>
