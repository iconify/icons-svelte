<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovde4bbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ovde4bbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dumbbell" {...props}></Icon>
