<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n89zesbhu.css';
import '../../css/p/pgc70abwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n89zesbhu"/><path class="pgc70abwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:building-solid" {...props}></Icon>
