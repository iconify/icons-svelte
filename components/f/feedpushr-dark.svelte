<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vutzp7v9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vutzp7v9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedpushr-dark" {...props}></Icon>
