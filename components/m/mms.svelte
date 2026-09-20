<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d50lqeb2v.css';
import '../../css/b/b8ii2dbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":327.084};
const content = `<path class="d50lqeb2v"/><path class="b8ii2dbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mms" {...props}></Icon>
