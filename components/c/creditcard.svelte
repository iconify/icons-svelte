<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enpcx5b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="enpcx5b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:creditcard" {...props}></Icon>
