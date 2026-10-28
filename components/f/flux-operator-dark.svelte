<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljh46-15w.css';
import '../../css/o/o50rx_7zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljh46-15w"/><path class="o50rx_7zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flux-operator-dark" {...props}></Icon>
