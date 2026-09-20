<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7y-pvuqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7y-pvuqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-hr-light" {...props}></Icon>
