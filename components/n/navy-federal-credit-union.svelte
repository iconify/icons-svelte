<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o42jkxb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o42jkxb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:navy-federal-credit-union" {...props}></Icon>
