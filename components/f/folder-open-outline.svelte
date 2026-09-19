<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oznaotbtq.css';
import '../../css/z/z8vf7-egw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oznaotbtq"/><path class="z8vf7-egw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:folder-open-outline" {...props}></Icon>
