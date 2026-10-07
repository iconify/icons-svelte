<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn69_sn7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn69_sn7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:block-default" {...props}></Icon>
