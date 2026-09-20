<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3fpsd3sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3fpsd3sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openshift-light" {...props}></Icon>
