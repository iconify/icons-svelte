<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmt3k8bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmt3k8bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:headphones2" {...props}></Icon>
