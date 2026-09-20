<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duvo0wbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duvo0wbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:download" {...props}></Icon>
