<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pha2xxb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pha2xxb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:body-shape2" {...props}></Icon>
