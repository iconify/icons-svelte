<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfuz5s9ob.css';
import '../../css/q/q8fvfdcmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="xfuz5s9ob"/><path class="q8fvfdcmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:lightbulb" {...props}></Icon>
