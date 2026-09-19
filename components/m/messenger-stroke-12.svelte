<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odh4hebtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="odh4hebtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:messenger-stroke-12" {...props}></Icon>
