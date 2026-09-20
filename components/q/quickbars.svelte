<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7bxye5gu.css';
import '../../css/f/f0tftrz9n.css';
import '../../css/h/h1bugcb5m.css';
import '../../css/y/yfst6cc1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j7bxye5gu"/><path class="f0tftrz9n"/><path class="h1bugcb5m"/><path class="yfst6cc1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickbars" {...props}></Icon>
