<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8qpv3buc.css';
import '../../css/a/ab4vmibnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o8qpv3buc"/><circle class="ab4vmibnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:gear-stroke-16" {...props}></Icon>
