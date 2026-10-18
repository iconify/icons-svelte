<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf3b3gb2z.css';
import '../../css/y/y9zlo3-ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wf3b3gb2z"/><path class="y9zlo3-ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biochar-48-bold" {...props}></Icon>
