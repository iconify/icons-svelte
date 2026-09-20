<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uatd2gfja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uatd2gfja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pet-paw" {...props}></Icon>
