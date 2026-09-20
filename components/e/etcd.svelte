<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdpm3zb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdpm3zb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:etcd" {...props}></Icon>
