<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o215ocbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o215ocbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chef-hat-one" {...props}></Icon>
