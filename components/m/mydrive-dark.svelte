<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekzz-41rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ekzz-41rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mydrive-dark" {...props}></Icon>
