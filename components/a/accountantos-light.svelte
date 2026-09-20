<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enqd_6bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1084,"height":1074};
const content = `<path class="enqd_6bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:accountantos-light" {...props}></Icon>
