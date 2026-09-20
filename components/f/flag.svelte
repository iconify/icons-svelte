<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrb-vva6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wrb-vva6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:flag" {...props}></Icon>
