<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw4tx68rp.css';
import '../../css/r/rqc7mdb1v.css';
import '../../css/c/cpgwot4ac.css';
import '../../css/v/v8ai3lb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="hw4tx68rp"/><path class="rqc7mdb1v"/><path class="cpgwot4ac"/><path class="v8ai3lb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:csv" {...props}></Icon>
