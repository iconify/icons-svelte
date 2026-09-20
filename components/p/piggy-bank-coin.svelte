<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db0of5bxd.css';
import '../../css/n/ndxq0db7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="db0of5bxd"/><path class="ndxq0db7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:piggy-bank-coin" {...props}></Icon>
